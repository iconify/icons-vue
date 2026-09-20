<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1uf-kbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1uf-kbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ceiling-lamp-line" /></template>
