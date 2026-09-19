<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v216tbc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="v216tbc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:first-order-alt" /></template>
