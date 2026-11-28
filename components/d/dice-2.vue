<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1-nljdwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-nljdwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dice-2" /></template>
