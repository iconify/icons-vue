<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfu-picse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cfu-picse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:handshake" /></template>
