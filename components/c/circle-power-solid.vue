<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aynsa_bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aynsa_bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-power-solid" /></template>
