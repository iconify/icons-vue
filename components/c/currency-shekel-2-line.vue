<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bss2tqi7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bss2tqi7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-shekel-2-line" /></template>
