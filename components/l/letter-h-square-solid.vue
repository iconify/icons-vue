<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7fu7w2an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7fu7w2an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-h-square-solid" /></template>
