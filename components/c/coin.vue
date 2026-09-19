<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg5fzvb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg5fzvb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coin" /></template>
