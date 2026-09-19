<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm_xmx2dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pm_xmx2dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flag" /></template>
