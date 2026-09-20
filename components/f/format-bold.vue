<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erc-qvbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erc-qvbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-bold" /></template>
