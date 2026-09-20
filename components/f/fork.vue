<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh8z_vbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rh8z_vbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fork" /></template>
