<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuuehgbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuuehgbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cake-slice-filled" /></template>
