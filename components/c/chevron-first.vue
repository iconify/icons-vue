<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkj05ncls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkj05ncls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevron-first" /></template>
