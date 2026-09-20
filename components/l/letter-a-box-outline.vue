<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uulbojbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uulbojbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-a-box-outline" /></template>
