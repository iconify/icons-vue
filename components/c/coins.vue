<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6rtucb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6rtucb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coins" /></template>
