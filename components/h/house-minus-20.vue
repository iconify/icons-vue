<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g25gybccv.css';
import '../../css/e/egh3d5cfd.css';
import '../../css/v/vvpeo-3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g25gybccv"/><path class="egh3d5cfd"/><path class="vvpeo-3dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-minus-20" /></template>
