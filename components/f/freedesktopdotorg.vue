<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiy7w4wnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiy7w4wnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:freedesktopdotorg" /></template>
