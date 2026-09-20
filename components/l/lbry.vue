<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo-d3i9sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo-d3i9sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lbry" /></template>
