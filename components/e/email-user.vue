<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li-ahdpxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="li-ahdpxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:email-user" /></template>
