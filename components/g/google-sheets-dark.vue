<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-t-9-bbm.css';
import '../../css/r/riiz-0est.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q-t-9-bbm"/><path class="riiz-0est"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-sheets-dark" /></template>
