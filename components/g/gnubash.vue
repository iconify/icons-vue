<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehqum42-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehqum42-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gnubash" /></template>
