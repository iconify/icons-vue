<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs-5p3fbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs-5p3fbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-down-fill" /></template>
