<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udydlndhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udydlndhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:esea" /></template>
