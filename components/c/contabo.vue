<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx_8t2b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx_8t2b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:contabo" /></template>
