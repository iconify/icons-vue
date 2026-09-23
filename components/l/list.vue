<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko5nd2b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko5nd2b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:list" /></template>
