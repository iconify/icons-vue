<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9qkdc_cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r9qkdc_cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:amount-down-filled" /></template>
