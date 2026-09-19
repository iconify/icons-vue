<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pre42p12x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pre42p12x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:inbox" /></template>
