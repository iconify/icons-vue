<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re8d6dfzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re8d6dfzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cells" /></template>
