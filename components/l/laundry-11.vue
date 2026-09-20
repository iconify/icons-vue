<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k40_dxbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="k40_dxbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:laundry-11" /></template>
