<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7oil4my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx7oil4my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:film-solid" /></template>
