<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw0_labpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dw0_labpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eslint-outline" /></template>
