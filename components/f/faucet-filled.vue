<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6a4xtm3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6a4xtm3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:faucet-filled" /></template>
