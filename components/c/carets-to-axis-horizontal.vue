<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbswtxmxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbswtxmxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:carets-to-axis-horizontal" /></template>
