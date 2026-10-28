<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo4n4ebjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo4n4ebjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bwt" /></template>
