<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amj4dacdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amj4dacdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-sun" /></template>
