<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8j5qb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8j5qb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-distribute-center-filled" /></template>
