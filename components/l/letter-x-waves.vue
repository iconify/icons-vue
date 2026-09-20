<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acut2rbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acut2rbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-waves" /></template>
