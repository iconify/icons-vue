<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-qtcu_5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o-qtcu_5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:circle-medium-outline" /></template>
