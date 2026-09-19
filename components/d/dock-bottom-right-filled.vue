<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh0iujzym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh0iujzym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-bottom-right-filled" /></template>
