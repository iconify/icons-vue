<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqcn2nvil.css';
import '../../css/j/jufokfbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqcn2nvil"/><path class="jufokfbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hortusfox" /></template>
