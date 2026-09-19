<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhch_fo3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhch_fo3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:database" /></template>
