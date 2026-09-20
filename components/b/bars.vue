<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evo6y-hhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evo6y-hhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:bars" /></template>
