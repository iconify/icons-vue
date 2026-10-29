<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih4kqxb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih4kqxb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-plus" /></template>
