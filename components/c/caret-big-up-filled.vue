<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx_bh6bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx_bh6bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-big-up-filled" /></template>
