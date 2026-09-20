<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn9txsb0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pn9txsb0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ingress" /></template>
