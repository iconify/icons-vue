<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb6mwqofg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qb6mwqofg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:heart" /></template>
