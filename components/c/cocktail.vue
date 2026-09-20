<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ra0p2rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9ra0p2rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cocktail" /></template>
