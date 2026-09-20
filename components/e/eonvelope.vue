<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4zh2mqii.css';
import '../../css/g/g0wt4tw1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4zh2mqii"/><path class="g0wt4tw1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eonvelope" /></template>
