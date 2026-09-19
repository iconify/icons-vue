<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1jarzbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1jarzbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-top-right-3-square-fill" /></template>
