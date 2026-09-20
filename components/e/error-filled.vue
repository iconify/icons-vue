<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mofy_3ahk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mofy_3ahk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:error-filled" /></template>
