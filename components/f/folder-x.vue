<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6p30emra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6p30emra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-x" /></template>
