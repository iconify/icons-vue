<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm76_sc_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm76_sc_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cabin" /></template>
