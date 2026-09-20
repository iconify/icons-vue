<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrq3cn4tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrq3cn4tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lutris" /></template>
