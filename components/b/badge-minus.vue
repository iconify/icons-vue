<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgtlrs60x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgtlrs60x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:badge-minus" /></template>
