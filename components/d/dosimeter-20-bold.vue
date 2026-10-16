<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b63t5_b0n.css';
import '../../css/u/ufacyhbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b63t5_b0n"/><path class="ufacyhbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dosimeter-20-bold" /></template>
