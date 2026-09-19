<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bucw1rb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bucw1rb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-1-thin" /></template>
