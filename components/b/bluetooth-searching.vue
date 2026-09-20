<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl6m2oa_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xl6m2oa_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:bluetooth-searching" /></template>
