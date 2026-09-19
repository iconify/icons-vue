<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey5jcwb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey5jcwb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:gitlab" /></template>
