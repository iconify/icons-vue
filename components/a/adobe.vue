<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jge61kaeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jge61kaeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:adobe" /></template>
