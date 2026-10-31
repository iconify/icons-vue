<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhcx4ioui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhcx4ioui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-litecoin-fill-round" /></template>
