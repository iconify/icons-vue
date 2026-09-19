<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpqyh0d1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xpqyh0d1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-location" /></template>
