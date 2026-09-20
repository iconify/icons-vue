<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyjk7gbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyjk7gbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:evcc-light" /></template>
