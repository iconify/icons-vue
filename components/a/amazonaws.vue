<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abc0zxb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abc0zxb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:amazonaws" /></template>
