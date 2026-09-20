<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3knuo1-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3knuo1-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-check" /></template>
