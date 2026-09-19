<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar1aq-_-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar1aq-_-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-quarter-filled" /></template>
