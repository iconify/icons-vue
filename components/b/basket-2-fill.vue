<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9hd6vbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9hd6vbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:basket-2-fill" /></template>
