<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdk2_smhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pdk2_smhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-center-horizontal-outline" /></template>
