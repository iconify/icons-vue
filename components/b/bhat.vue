<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5e054bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5e054bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bhat" /></template>
