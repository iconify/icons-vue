<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_3m48bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x_3m48bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:bitty-filled" /></template>
