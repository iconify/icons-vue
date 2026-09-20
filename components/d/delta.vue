<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er5-kobdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="er5-kobdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:delta" /></template>
