<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4ldiibyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ldiibyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-drop-line" /></template>
