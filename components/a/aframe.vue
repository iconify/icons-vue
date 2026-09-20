<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e040unj3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e040unj3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aframe" /></template>
