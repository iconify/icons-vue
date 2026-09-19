<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4wa_q_fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="h4wa_q_fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baby-bold" /></template>
