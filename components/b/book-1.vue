<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e62wtrb5d.css';
import '../../css/s/sksbtdbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e62wtrb5d"/><path class="sksbtdbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:book-1" /></template>
