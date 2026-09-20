<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7payabnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7payabnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:key-2-fill" /></template>
