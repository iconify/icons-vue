<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcnx9acjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="xcnx9acjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:heading-level-5" /></template>
