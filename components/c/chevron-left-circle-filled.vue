<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_q4f9j6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_q4f9j6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-left-circle-filled" /></template>
