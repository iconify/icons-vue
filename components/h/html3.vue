<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8h50pnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8h50pnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:html3" /></template>
