<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgfs6lbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qgfs6lbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:border-officer-with-open-suitcase" /></template>
