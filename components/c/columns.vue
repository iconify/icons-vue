<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgx5tmbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="zgx5tmbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:columns" /></template>
