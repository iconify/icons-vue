<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uikk2ibkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uikk2ibkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:building" /></template>
