<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia4prxbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia4prxbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:acorn-filled" /></template>
