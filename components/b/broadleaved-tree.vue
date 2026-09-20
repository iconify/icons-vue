<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moehyo9mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="moehyo9mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:broadleaved-tree" /></template>
