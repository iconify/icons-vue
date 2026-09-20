<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0f9fm8gg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="m0f9fm8gg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:dashboard-filled" /></template>
