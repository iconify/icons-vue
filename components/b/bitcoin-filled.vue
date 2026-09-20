<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7ogi1brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c7ogi1brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bitcoin-filled" /></template>
