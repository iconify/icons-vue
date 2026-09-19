<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5o2m-7uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5o2m-7uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-error" /></template>
