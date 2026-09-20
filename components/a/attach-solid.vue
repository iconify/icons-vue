<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj7_yrpex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wj7_yrpex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:attach-solid" /></template>
