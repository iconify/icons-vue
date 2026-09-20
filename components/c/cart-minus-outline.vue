<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc-6m5bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vc-6m5bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cart-minus-outline" /></template>
