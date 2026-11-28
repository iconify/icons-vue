<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4dw95f-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4dw95f-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-check" /></template>
