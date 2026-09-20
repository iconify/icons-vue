<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbn2wh0re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbn2wh0re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ichi" /></template>
