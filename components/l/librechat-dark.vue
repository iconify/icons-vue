<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcm3g6b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vcm3g6b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librechat-dark" /></template>
