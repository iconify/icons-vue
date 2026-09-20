<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml_lf0bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ml_lf0bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:gift-11" /></template>
