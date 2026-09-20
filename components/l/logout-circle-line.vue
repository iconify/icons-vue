<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkj8pk19w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkj8pk19w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-circle-line" /></template>
