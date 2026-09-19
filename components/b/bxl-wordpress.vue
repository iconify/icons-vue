<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtczv9bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtczv9bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-wordpress" /></template>
