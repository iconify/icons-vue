<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u46ksmjsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u46ksmjsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:health-book-fill" /></template>
