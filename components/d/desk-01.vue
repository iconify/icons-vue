<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg5agddeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg5agddeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:desk-01" /></template>
