<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbcz6wiur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbcz6wiur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:luggage" /></template>
