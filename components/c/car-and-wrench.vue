<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6r3qlnuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o6r3qlnuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-and-wrench" /></template>
