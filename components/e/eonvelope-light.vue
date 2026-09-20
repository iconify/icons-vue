<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyemvd5bc.css';
import '../../css/v/vg0td9b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyemvd5bc"/><path class="vg0td9b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eonvelope-light" /></template>
