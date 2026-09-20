<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibf9d8bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibf9d8bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:briefcase-5-fill" /></template>
