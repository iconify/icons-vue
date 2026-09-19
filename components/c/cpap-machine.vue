<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3nib0-4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y3nib0-4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-machine" /></template>
