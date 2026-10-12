<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko2focc5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko2focc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bed-filled" /></template>
