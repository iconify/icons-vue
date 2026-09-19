<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egkp_3bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="egkp_3bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:chevron-down" /></template>
