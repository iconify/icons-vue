<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2s0kvbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2s0kvbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-sharp" /></template>
