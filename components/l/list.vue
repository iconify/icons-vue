<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwovrsb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwovrsb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:list" /></template>
