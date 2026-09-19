<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgwk9ybgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tgwk9ybgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-minus" /></template>
