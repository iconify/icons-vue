<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5ppxm0by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ppxm0by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-minus-outline" /></template>
