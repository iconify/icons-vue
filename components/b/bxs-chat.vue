<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atr529omg.css';
import '../../css/t/tlb5s_7xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atr529omg"/><path class="tlb5s_7xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chat" /></template>
