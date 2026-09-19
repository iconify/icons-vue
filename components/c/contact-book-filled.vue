<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7u6qacet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7u6qacet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:contact-book-filled" /></template>
