<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1jojacbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1jojacbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:calendar-2-fill" /></template>
