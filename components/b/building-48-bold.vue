<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwzk_6p2e.css';
import '../../css/u/uy6zwjbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pwzk_6p2e"/><path class="uy6zwjbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-48-bold" /></template>
