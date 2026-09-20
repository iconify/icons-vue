<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7i0xybwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p7i0xybwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:device-play-filled" /></template>
