<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qblge1bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qblge1bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:flag" /></template>
