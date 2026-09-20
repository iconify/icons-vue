<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1lkljlcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1lkljlcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-solid" /></template>
