<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bue59f0bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bue59f0bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bookmark-off" /></template>
