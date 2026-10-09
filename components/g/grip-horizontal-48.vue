<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_szgrglp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s_szgrglp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grip-horizontal-48" /></template>
