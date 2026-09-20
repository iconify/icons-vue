<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gte1b_zmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gte1b_zmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:contract-outline" /></template>
