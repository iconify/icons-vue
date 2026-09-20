<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts6_ikawi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts6_ikawi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-right-down" /></template>
