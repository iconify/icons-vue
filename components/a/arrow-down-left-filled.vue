<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5slksxri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5slksxri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-left-filled" /></template>
