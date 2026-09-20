<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7gsv6u-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":93,"height":20};
const content = `<path clip-rule="evenodd" class="u7gsv6u-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:beacon" /></template>
