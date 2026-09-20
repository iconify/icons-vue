<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tecmeuo1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tecmeuo1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-right-up-circle-filled" /></template>
