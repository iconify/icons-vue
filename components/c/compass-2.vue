<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-2j-zbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j-2j-zbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:compass-2" /></template>
