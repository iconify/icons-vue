<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of77a-g0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of77a-g0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-right-linear" /></template>
