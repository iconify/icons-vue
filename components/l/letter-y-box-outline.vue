<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clr47hbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clr47hbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-y-box-outline" /></template>
