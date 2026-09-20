<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r59434b-s.css';
import '../../css/l/llsk85l6z.css';
import '../../css/m/mtah3b3np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r59434b-s"/><path class="llsk85l6z"/><path class="mtah3b3np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-product-scale" /></template>
