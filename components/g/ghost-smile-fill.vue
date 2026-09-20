<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlga79byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlga79byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-smile-fill" /></template>
