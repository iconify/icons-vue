<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsai45bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsai45bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cylinder-filled" /></template>
