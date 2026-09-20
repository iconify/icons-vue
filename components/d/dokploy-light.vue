<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzfvl7dyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzfvl7dyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dokploy-light" /></template>
