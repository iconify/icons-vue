<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcg3ghv9p.css';
import '../../css/j/j85tku0cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mcg3ghv9p"/><path class="j85tku0cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:code-alt" /></template>
