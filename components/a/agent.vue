<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we144-bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="we144-bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:agent" /></template>
