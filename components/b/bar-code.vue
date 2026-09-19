<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1ebk-e9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c1ebk-e9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bar-code" /></template>
