<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyhl03b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyhl03b9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-open-fill" /></template>
