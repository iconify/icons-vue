<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/najn0wbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="najn0wbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:calendar-f" /></template>
