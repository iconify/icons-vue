<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvacjcbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvacjcbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-slash-2" /></template>
