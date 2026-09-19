<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpma81dsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpma81dsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:c" /></template>
