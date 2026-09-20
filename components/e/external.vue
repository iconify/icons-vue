<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm_kizbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="pm_kizbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:external" /></template>
