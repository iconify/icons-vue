<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gev1hsbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gev1hsbtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:buzzfeed" /></template>
