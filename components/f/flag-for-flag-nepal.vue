<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="g90iejhyo"/><path class="iu6pvhb7g"/><path class="mw4lkpbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-nepal" /></template>
<style>
.g90iejhyo {
  fill: var(--svg-color--22408b, #22408B);
  d: path("M27.796 19L8 5v26h19.796L15.918 19z");
}

.iu6pvhb7g {
  fill: var(--svg-color--dd2f45, #DD2F45);
  d: path("M25 18L9 7.196V30h16L13.574 18z");
}

.mw4lkpbnz {
  fill: var(--svg-color--fff, #FFF);
  d: path("M14.291 24.041l.586-.816l-1 .098l.1-1l-.817.586l-.414-.916l-.414.916l-.817-.586l.099 1l-1-.098l.586.816l-.916.414l.916.414l-.586.816l1-.098l-.099 1l.817-.586l.414.916l.414-.916l.817.586l-.1-1l1 .098l-.586-.816l.916-.414zm-1.546-7.147l.001.002l.001-.002l.018.002c1.468 0 2.66-1.13 2.784-2.567a3.2 3.2 0 0 1-1.595 1.442l-.175-.244l.611-.276l-.611-.276l.391-.545l-.668.066l.067-.668l-.546.391l-.276-.612l-.276.612l-.546-.391l.067.668l-.668-.066l.391.545l-.611.276l.611.276l-.167.233a3.203 3.203 0 0 1-1.566-1.431a2.795 2.795 0 0 0 2.763 2.565z");
}

</style>
