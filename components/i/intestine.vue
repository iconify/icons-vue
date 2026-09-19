<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s213jrbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s213jrbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intestine" /></template>
