<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oda7t_bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oda7t_bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:loveseat" /></template>
