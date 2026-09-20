<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m52gdcb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m52gdcb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache-parquet" /></template>
