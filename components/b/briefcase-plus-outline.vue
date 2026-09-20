<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efo8qcbxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efo8qcbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:briefcase-plus-outline" /></template>
