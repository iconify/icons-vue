<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh36egyhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh36egyhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-up" /></template>
