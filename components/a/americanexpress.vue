<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwi5op4lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwi5op4lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:americanexpress" /></template>
