<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kif8d7ioj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kif8d7ioj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-left-02" /></template>
