<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsz0ddbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsz0ddbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-search-fill" /></template>
