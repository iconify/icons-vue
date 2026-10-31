<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijp6pjbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijp6pjbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:contacts-fill-round" /></template>
