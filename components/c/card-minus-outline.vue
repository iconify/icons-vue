<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwcd--kov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwcd--kov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-minus-outline" /></template>
