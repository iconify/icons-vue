<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsmvn1bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsmvn1bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:eco-house-remix" /></template>
