<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydunrvbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydunrvbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bulleted-list" /></template>
