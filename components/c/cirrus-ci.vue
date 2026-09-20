<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="ugn0xccey"/><path class="a64-9bb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:cirrus-ci" /></template>
<style>
.a64-9bb6c {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M164.966 70.5c12.594 0 22.795 10.241 22.795 22.863a22.84 22.84 0 0 1-7.912 17.318A22.84 22.84 0 0 1 187.761 128c0 6.92-3.066 13.126-7.913 17.32a22.84 22.84 0 0 1 7.913 17.317c0 12.496-9.998 22.658-22.418 22.86l-.377.003H73.783a5.545 5.545 0 0 1-.194-11.086l.194-.004h91.183c6.46 0 11.706-5.266 11.706-11.773c0-6.42-5.107-11.633-11.448-11.77l-.258-.004H73.783a5.545 5.545 0 0 1-.194-11.086l.194-.004h91.183c6.46 0 11.706-5.266 11.706-11.773c0-6.42-5.107-11.633-11.448-11.77l-.258-.003H73.783a5.545 5.545 0 0 1-.194-11.087l.194-.003h91.183c6.46 0 11.706-5.267 11.706-11.774c0-6.42-5.107-11.633-11.448-11.77l-.258-.003a5.545 5.545 0 1 1 0-11.09");
}

.ugn0xccey {
  cx: 128px;
  cy: 128px;
  r: 128px;
}

</style>
