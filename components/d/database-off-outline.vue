<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq5gymbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq5gymbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-off-outline" /></template>
