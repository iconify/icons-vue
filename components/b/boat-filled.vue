<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhr69gdnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhr69gdnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:boat-filled" /></template>
