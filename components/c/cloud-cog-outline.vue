<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcj88du6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcj88du6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-cog-outline" /></template>
