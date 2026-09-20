<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz7on2bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz7on2bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dots-fill" /></template>
