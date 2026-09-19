<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlg1cmb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xlg1cmb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-turn-down-right" /></template>
