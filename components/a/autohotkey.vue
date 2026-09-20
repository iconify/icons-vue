<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1n3j_hwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1n3j_hwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:autohotkey" /></template>
