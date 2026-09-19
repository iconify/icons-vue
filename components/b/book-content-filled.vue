<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9mdn9b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9mdn9b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:book-content-filled" /></template>
