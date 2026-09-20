<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in9j5j9wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in9j5j9wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-right-solid" /></template>
