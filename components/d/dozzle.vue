<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaz5-_bhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zaz5-_bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dozzle" /></template>
