<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvc_sdbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yvc_sdbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:heart-crack" /></template>
