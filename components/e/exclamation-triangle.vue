<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikia-1bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikia-1bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:exclamation-triangle" /></template>
