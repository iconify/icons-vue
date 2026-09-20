<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs6uoeyib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs6uoeyib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-up-left-square-solid" /></template>
