<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oymhbubdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oymhbubdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-back-line" /></template>
