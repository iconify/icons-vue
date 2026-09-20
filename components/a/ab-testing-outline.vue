<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlxs1tz2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mlxs1tz2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ab-testing-outline" /></template>
