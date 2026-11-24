<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whk1n9bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="whk1n9bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-question-mark-filled" /></template>
