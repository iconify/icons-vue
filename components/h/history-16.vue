<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfkp03q-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pfkp03q-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:history-16" /></template>
