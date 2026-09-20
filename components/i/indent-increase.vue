<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxuiy-buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxuiy-buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:indent-increase" /></template>
