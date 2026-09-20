<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uub0g_gkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uub0g_gkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deutsche-post" /></template>
