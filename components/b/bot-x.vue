<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk49mkgwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk49mkgwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:bot-x" /></template>
