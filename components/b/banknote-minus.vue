<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj0p3sbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj0p3sbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:banknote-minus" /></template>
