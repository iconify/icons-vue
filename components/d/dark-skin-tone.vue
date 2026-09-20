<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cf5ovs9yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:dark-skin-tone" /></template>
<style>
.cf5ovs9yz {
  fill: var(--svg-color--584539, #584539);
  d: path("M10 10h108v108H10z");
}

</style>
