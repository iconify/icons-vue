<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv2m5ub-n.css';
import '../../css/j/jmyubu8dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hv2m5ub-n"/><path class="jmyubu8dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:first-aid" /></template>
