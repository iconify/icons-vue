<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq0s4iban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq0s4iban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-2-line" /></template>
