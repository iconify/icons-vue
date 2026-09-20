<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4jwp3d8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i4jwp3d8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:check-out" /></template>
