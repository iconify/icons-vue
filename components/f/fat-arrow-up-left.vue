<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crrtghkve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crrtghkve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-arrow-up-left" /></template>
