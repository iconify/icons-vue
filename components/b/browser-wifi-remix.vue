<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g77xi_7ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g77xi_7ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:browser-wifi-remix" /></template>
