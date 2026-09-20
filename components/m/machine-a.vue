<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa76olytg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fa76olytg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:machine-a" /></template>
