<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3pqtucgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3pqtucgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-swap-horizontal" /></template>
