<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8m6mibuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8m6mibuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dashboard" /></template>
