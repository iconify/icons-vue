<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txo1x1bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txo1x1bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-right" /></template>
