<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv-3p-s8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dv-3p-s8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:light-rail" /></template>
