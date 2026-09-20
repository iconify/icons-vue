<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dluyn9c8v.css';
import '../../css/g/gj051ober.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dluyn9c8v"/><path class="gj051ober"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-bag" /></template>
