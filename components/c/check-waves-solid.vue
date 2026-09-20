<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuzch45me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuzch45me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-waves-solid" /></template>
