<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnj339csp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnj339csp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:chart-bar-alt" /></template>
