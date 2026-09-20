<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dclwapbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="dclwapbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:fish-cleaning" /></template>
