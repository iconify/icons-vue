<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhbtcways.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yhbtcways"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:drawer-documents" /></template>
