<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt-kaubdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt-kaubdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:currencyexchange" /></template>
