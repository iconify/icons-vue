<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agl78fbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="agl78fbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bookmark-filled" /></template>
