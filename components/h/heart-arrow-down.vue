<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlm5yub9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlm5yub9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:heart-arrow-down" /></template>
