<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e618xc-zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="e618xc-zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:bug" /></template>
