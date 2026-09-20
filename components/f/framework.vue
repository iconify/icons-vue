<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cufzc4b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cufzc4b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:framework" /></template>
