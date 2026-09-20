<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anmx89xew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anmx89xew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-swap-horizontal-filled" /></template>
