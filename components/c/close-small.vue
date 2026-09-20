<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5_a1ncx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="oc5_a1ncx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:close-small" /></template>
