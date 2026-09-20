<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juk_1pbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juk_1pbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-arrow-down-outline" /></template>
