<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6z_85bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y6z_85bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fire-extinguisher" /></template>
