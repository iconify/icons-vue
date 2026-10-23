<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-x4nib5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-x4nib5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:archive-restore" /></template>
