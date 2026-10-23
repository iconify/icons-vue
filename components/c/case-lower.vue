<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blrazoble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blrazoble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:case-lower" /></template>
