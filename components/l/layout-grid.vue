<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntw0kh4xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntw0kh4xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:layout-grid" /></template>
