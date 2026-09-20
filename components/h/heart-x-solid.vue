<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgkzzvb4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgkzzvb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-x-solid" /></template>
