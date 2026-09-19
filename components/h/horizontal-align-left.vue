<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5px0cbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5px0cbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-align-left" /></template>
