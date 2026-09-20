<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydz5a80uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydz5a80uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bleach" /></template>
