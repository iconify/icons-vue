<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-cttubcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-cttubcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:link-chain-solid" /></template>
