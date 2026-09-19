<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqx0cbb0u.css';
import '../../css/q/qrs5x0bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iqx0cbb0u"/><path class="qrs5x0bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:clickhouse" /></template>
