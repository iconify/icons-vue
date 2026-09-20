<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd9lf2bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dd9lf2bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hospital-bold" /></template>
