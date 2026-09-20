<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":264};
const content = `<path class="tvfgz6syz"/><circle class="qyu8aqybw"/><path class="xvu-x1nfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-optimize" /></template>
<style>
.qyu8aqybw {
  cx: 35.94px;
  cy: 131.538px;
  r: 35.94px;
  fill: var(--svg-color--8430ce, #8430ce);
}

.tvfgz6syz {
  fill: var(--svg-color--b366f6, #b366f6);
  d: path("M168.2 131.117c-.46-19.95-16.888-35.815-36.842-35.579H36.36v71.157h61.525v59.84a34.916 34.916 0 0 0 34.194 36.842a36.48 36.48 0 0 0 36.12-36.842z");
}

.xvu-x1nfj {
  fill: var(--svg-color--c58af8, #c58af8);
  d: path("M255.913 35.76C255.714 15.951 239.6 0 219.793 0h-97.164c-18.46 1.853-32.513 17.388-32.513 35.94s14.054 34.087 32.513 35.94h62.247v59.779a35.579 35.579 0 1 0 71.097 0z");
}

</style>
