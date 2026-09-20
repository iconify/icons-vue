<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0y1jhidk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0y1jhidk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bell" /></template>
