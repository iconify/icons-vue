<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_ipq_b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ipq_b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jingle-bells-gloss" /></template>
