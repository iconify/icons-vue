<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stf__337k.css';
import '../../css/y/yjte_gbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="stf__337k"/><path class="yjte_gbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:log-16" /></template>
