<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6p14o9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_6p14o9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-copy" /></template>
