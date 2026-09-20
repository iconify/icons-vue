<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4eri6sxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4eri6sxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:geeksforgeeks" /></template>
