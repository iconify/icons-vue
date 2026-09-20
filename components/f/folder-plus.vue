<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ieodu4--x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ieodu4--x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:folder-plus" /></template>
