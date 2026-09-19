<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ohlcdxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_ohlcdxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-xamento" /></template>
