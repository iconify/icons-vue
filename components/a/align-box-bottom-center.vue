<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/robljacxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="robljacxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-box-bottom-center" /></template>
