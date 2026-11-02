<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td4k7im4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td4k7im4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-x-fill" /></template>
