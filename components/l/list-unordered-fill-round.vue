<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-5v2fb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-5v2fb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-unordered-fill-round" /></template>
