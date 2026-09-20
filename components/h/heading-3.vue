<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig7lx8b2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig7lx8b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-3" /></template>
