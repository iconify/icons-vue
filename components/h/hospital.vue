<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm79drjpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm79drjpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hospital" /></template>
