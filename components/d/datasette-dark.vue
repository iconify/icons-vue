<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvtboac2u.css';
import '../../css/m/m23pcacuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bvtboac2u"/><path class="m23pcacuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:datasette-dark" /></template>
