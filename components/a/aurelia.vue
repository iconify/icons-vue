<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz5rt2evi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz5rt2evi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:aurelia" /></template>
