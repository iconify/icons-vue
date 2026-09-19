<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvu7ot9vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="vvu7ot9vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:cloud-up" /></template>
