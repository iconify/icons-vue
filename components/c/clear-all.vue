<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmhvz6byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmhvz6byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:clear-all" /></template>
