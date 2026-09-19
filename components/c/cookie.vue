<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogurkac2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ogurkac2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cookie" /></template>
