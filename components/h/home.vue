<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbk574aal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wbk574aal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:home" /></template>
