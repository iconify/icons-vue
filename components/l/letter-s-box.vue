<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh5f-2kxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh5f-2kxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-s-box" /></template>
