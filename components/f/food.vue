<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zceg7w4_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zceg7w4_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:food" /></template>
