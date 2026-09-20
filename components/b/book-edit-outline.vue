<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l469j5b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l469j5b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-edit-outline" /></template>
