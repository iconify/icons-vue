<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njb366n5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="njb366n5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:credit-card-1-solid" /></template>
