<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v367-ccpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v367-ccpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-shrink-v" /></template>
