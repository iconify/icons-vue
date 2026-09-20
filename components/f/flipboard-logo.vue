<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8isv-k1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8isv-k1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:flipboard-logo" /></template>
