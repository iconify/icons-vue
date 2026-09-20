<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmlrazf5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmlrazf5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:edit-fill" /></template>
