<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpze0lz-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpze0lz-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle" /></template>
