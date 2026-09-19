<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgjx7bwna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgjx7bwna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-grid-alt" /></template>
