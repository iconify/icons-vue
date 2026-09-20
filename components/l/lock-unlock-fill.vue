<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cngzuebbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cngzuebbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-unlock-fill" /></template>
