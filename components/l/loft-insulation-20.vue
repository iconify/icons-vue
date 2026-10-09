<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbx5zccce.css';
import '../../css/q/qi4e-mbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fbx5zccce"/><path class="qi4e-mbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:loft-insulation-20" /></template>
