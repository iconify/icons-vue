<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4x64lg8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n4x64lg8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:direction" /></template>
