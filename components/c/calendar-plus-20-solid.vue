<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwmik4bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hwmik4bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-plus-20-solid" /></template>
