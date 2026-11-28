<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dih7k4bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dih7k4bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:briefcase-search" /></template>
