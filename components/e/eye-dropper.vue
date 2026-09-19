<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efm14ibwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efm14ibwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:eye-dropper" /></template>
