<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8dzo7vbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8dzo7vbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-r" /></template>
