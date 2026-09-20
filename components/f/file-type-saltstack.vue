<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="smf0ljbvc"/><path class="nzulr5bvy"/><path class="ti-znvnhl"/><path class="btz5v9byb"/><path class="aoxaw7far"/><path class="kr-e0mh7y"/><path class="cj0jycblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-saltstack" /></template>
<style>
.aoxaw7far {
  fill: var(--svg-color--75bed5, #75bed5);
  d: path("m27.382 16.053l-6.274 3.137v-6.177l-6.4 3.062l.055 6.453v6.21l6.343-3.172v-.035l6.276-3.131z");
}

.btz5v9byb {
  fill: var(--svg-color--4396b9, #4396b9);
  d: path("m14.764 22.4l-.053-6.32l-6.355-3.168L2 9.774v6.412l.061 6.21l6.146 3.073l.184.092l.013.006l6.359 3.172z");
}

.cj0jycblp {
  fill: var(--svg-color--b8dde8, #b8dde8);
  d: path("m17.25 6.653l6.406 3.241L30 6.721l-6.47-3.309l-4.372 2.256l-4.7-2.407l-6.383 3.321L2 9.774l6.356 3.139l6.355 3.163l6.4-3.062L14.638 9.7l-.083.043l-.016-.008l.1-.035l2.612-1.3z");
}

.kr-e0mh7y {
  fill: var(--svg-color--75bed5, #75bed5);
  d: path("m30 13.065l-6.343 3.171V9.893L30 6.721z");
}

.nzulr5bvy {
  fill: var(--svg-color--b8dde8, #b8dde8);
  d: path("m25.722 15.2l1.66.849l-6.258 3.129l-.016-4.175l2.548 1.229z");
}

.smf0ljbvc {
  fill: var(--svg-color--4396b9, #4396b9);
  d: path("M17.25 11.04V6.653l6.406 3.241v6.343l-2.548-1.229v-1.995z");
}

.ti-znvnhl {
  fill: var(--svg-color--75bed5, #75bed5);
  d: path("M17.25 8.407L14.638 9.7l2.612 1.34z");
}

</style>
