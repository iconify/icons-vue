<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0yewobdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0yewobdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gift-outline" /></template>
