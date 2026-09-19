<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfvdzab5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfvdzab5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:attachment" /></template>
