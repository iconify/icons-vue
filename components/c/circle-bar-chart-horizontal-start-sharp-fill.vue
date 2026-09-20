<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo28neb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xo28neb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-horizontal-start-sharp-fill" /></template>
