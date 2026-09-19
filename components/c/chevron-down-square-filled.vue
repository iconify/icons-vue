<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj3qj13na.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj3qj13na"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chevron-down-square-filled" /></template>
