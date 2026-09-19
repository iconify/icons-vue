<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o18pi7bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="o18pi7bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:check-compact" /></template>
