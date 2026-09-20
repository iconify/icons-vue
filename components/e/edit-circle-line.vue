<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5hzbmbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5hzbmbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-circle-line" /></template>
