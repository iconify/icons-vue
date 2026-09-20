<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfk1jzxah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfk1jzxah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:check-check" /></template>
