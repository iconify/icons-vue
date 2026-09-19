<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmk0ribem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmk0ribem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:help-outline" /></template>
