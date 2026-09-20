<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7el2-bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="o7el2-bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:cutlery-expressive" /></template>
