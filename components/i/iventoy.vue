<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvoz7pz8e.css';
import '../../css/g/glrhpswps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lvoz7pz8e"/><path class="glrhpswps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:iventoy" /></template>
