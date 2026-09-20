<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1_9seb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1_9seb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:g2g" /></template>
