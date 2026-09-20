<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/reck4ybkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="reck4ybkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:basket-solid" /></template>
