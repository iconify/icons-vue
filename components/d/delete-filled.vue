<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veg-jkd-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veg-jkd-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:delete-filled" /></template>
