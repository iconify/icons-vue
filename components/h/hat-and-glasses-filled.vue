<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-69cibvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-69cibvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:hat-and-glasses-filled" /></template>
