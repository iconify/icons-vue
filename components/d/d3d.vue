<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a995obcgw"/><path class="rco8feb6s"/><path class="t9bhgkb2j"/><path class="g8p1pjb2t"/><path class="a3u4no1du"/><path clip-rule="evenodd" class="phtmq-3fx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:d3d" /></template>
<style>
.a3u4no1du {
  fill: var(--svg-color--82cef0, #82cef0);
  d: path("m17.961 10.14l2.766-.998l-3.688-4.037L12.076 3v3l5.89 4.14z");
}

.a995obcgw {
  fill: var(--svg-color--46b5e0, #46b5e0);
  d: path("m3.29 9.284l.506 5.335l2.75 4.712l1.707-2.11l-2.198-6.868z");
}

.ft5dv1b6b {
  fill: none;
}

.g8p1pjb2t {
  fill: var(--svg-color--e3f4fc, #e3f4fc);
  d: path("m6.038 10.14l-2.765-.998L6.96 5.105L11.924 3v3l-5.891 4.14z");
}

.phtmq-3fx {
  fill: var(--svg-color--b9e2fe, #b9e2fe);
  fill-rule: evenodd;
  d: path("m17.814 10.44l-5.803-4.167l-5.804 4.168l2.215 6.741H15.6l2.22-6.741zM7.582 13.72l4.429 3.25l4.429-3.25l-1.691-5.264H9.272z");
}

.rco8feb6s {
  fill: var(--svg-color--0196da, #0196da);
  d: path("m20.689 9.284l-.502 5.335l-2.749 4.712l-1.729-2.127l2.22-6.85z");
}

.t9bhgkb2j {
  fill: var(--svg-color--87c9eb, #87c9eb);
  d: path("M15.633 17.291H8.44l-1.697 2.122L12.093 21l5.182-1.587z");
}

</style>
