<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i50zk7duk.css';
import '../../css/a/a_3ga6bbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i50zk7duk"/><path class="a_3ga6bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:eraser" /></template>
