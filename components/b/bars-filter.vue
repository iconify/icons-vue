<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0s1ki6od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0s1ki6od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bars-filter" /></template>
