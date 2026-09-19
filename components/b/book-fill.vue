<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d11dj0w2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d11dj0w2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:book-fill" /></template>
