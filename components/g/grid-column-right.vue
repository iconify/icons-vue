<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x384x5lmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x384x5lmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-column-right" /></template>
