<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7fvj6z2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s7fvj6z2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:guitar" /></template>
