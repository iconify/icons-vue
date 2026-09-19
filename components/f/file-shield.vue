<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dds184q7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="dds184q7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-shield" /></template>
