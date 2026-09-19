<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k71cscbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":256};
const content = `<path class="k71cscbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital-colon" /></template>
