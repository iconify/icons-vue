<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipcu34bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipcu34bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:add-to-cart" /></template>
