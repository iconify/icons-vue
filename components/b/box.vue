<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc71pfyul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc71pfyul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:box" /></template>
