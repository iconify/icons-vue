<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcc4fsl0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="pcc4fsl0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominonine" /></template>
