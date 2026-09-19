<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbhyi1bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbhyi1bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:diamond-alt-filled" /></template>
