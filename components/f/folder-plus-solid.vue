<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nam14s5tq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nam14s5tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-plus-solid" /></template>
