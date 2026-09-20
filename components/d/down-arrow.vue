<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq1aprlew.css';
import '../../css/l/l2uzblb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="rq1aprlew"/><path class="l2uzblb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:down-arrow" /></template>
