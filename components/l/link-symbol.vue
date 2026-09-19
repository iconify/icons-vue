<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfw8wabap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wfw8wabap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:link-symbol" /></template>
