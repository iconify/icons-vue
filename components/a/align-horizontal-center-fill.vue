<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk7vp6b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk7vp6b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-center-fill" /></template>
