<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa6gfacmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa6gfacmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat" /></template>
