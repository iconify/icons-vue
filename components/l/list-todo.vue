<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr1-48blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr1-48blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-todo" /></template>
