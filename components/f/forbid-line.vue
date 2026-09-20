<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezt2hxb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezt2hxb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forbid-line" /></template>
