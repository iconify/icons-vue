<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2515opfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a2515opfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-heart" /></template>
