<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itfxq4bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itfxq4bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bytestash" /></template>
