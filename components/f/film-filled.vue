<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx1iz5rcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx1iz5rcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:film-filled" /></template>
