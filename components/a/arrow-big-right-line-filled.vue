<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayizykitk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayizykitk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-right-line-filled" /></template>
