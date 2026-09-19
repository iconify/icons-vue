<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtp3hzbje.css';
import '../../css/t/tw9pjxlco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wtp3hzbje"/><path class="tw9pjxlco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-internet-services" /></template>
