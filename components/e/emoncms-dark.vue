<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a60v1_jqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a60v1_jqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emoncms-dark" /></template>
