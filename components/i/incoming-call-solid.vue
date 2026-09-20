<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3vpn-b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p3vpn-b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:incoming-call-solid" /></template>
