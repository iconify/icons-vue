<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctoyw6bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ctoyw6bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle" /></template>
