<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2v5b6b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2v5b6b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:font-color-filled" /></template>
