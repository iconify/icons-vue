<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uge65rbva.css';
import '../../css/p/pq7bzbb4c.css';
import '../../css/e/e-neq9bwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uge65rbva"/><path class="pq7bzbb4c"/><path class="e-neq9bwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cart-outline" /></template>
