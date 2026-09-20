<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3nf8db3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3nf8db3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:controller-wireless-remix" /></template>
