<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo6c03b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo6c03b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-waterfall-sharp-fill" /></template>
