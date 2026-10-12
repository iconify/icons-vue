<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdfq_js4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdfq_js4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gauge-filled" /></template>
