<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx5kbcrzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx5kbcrzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:archive-solid" /></template>
