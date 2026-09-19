<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpxjcbvi.css';
import '../../css/g/gpd_jwbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zbpxjcbvi"/><path class="gpd_jwbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:blender" /></template>
