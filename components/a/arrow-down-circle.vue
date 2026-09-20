<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cofje1bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cofje1bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-down-circle" /></template>
