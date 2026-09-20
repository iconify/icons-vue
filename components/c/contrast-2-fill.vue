<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4c-gkjcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4c-gkjcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contrast-2-fill" /></template>
