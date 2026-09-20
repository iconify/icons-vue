<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1_txq_7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="u1_txq_7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:dot" /></template>
