<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_3x2pb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e_3x2pb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-down-from-payment-card-in-slot" /></template>
