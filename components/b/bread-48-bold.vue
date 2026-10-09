<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udf9libzz.css';
import '../../css/a/a8yx3tbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="udf9libzz"/><path class="a8yx3tbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bread-48-bold" /></template>
