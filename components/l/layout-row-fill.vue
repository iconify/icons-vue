<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lctz0c0bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lctz0c0bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-row-fill" /></template>
