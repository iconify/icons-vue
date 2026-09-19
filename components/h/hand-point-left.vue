<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flhscpbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="flhscpbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-point-left" /></template>
