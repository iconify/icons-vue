<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz_ilzudp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-cancel-rounded" /></template>
<style>
.nz_ilzudp {
  fill: currentColor;
  d: path("m18.006 16.42l-1.752 1.732q-.146.146-.344.156t-.364-.156q-.16-.165-.16-.354t.16-.354l1.746-1.752l-1.746-1.733q-.16-.14-.16-.34t.16-.367q.166-.166.354-.166t.354.166l1.752 1.752l1.733-1.752q.146-.166.344-.166t.363.166q.16.165.16.354t-.16.353l-1.727 1.733l1.727 1.752q.14.14.15.341t-.15.367q-.165.165-.354.165t-.353-.165zM9.269 19q-.329 0-.549-.22t-.22-.55v-5.576L3.104 5.83q-.068-.068-.086-.153T3 5.519q0-.202.14-.36Q3.28 5 3.52 5h11.96q.24 0 .38.159q.14.158.14.36q0 .073-.018.159t-.086.153L10.5 12.654v5.577q0 .328-.22.549t-.55.22z");
}

</style>
