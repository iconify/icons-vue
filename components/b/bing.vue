<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcgl4ebri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tcgl4ebri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:bing" /></template>
