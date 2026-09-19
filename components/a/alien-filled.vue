<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxefai00q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxefai00q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alien-filled" /></template>
