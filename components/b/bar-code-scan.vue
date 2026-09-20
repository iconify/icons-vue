<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvuxhbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvuxhbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bar-code-scan" /></template>
