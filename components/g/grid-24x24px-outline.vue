<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfi5d0nul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfi5d0nul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:grid-24x24px-outline" /></template>
