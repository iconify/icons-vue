<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oueemn-9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oueemn-9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:brazilian-real-sign" /></template>
