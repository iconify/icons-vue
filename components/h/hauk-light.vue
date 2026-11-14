<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5-noybbr.css';
import '../../css/v/v068-hf6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5-noybbr"/><path class="v068-hf6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hauk-light" /></template>
