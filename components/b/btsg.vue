<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvfz0gvjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvfz0gvjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:btsg" /></template>
