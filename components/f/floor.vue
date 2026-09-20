<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xesbq9znz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xesbq9znz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:floor" /></template>
