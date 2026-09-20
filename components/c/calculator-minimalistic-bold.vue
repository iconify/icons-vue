<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-vtm-dnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-vtm-dnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calculator-minimalistic-bold" /></template>
