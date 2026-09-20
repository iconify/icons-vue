<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-pkdf3ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pkdf3ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:discount-box" /></template>
