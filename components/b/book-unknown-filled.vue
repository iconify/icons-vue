<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0me2lblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0me2lblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:book-unknown-filled" /></template>
