<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv2wyhb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wv2wyhb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:digital-totem-with-info-i" /></template>
