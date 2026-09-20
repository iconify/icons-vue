<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9s00j82r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="t9s00j82r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading" /></template>
