<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6h6mpbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6h6mpbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock-password" /></template>
