<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djxii9bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djxii9bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:code" /></template>
