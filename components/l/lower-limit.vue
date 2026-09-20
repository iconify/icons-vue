<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf7qtd1bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nf7qtd1bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:lower-limit" /></template>
