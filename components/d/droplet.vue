<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbyi9vbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbyi9vbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:droplet" /></template>
