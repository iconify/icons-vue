<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcew92bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcew92bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-left-sharp-fill" /></template>
