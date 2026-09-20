<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8poacjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8poacjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:attatch" /></template>
