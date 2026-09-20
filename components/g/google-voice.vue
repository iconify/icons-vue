<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q__ikjbpe.css';
import '../../css/u/u53z4igoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q__ikjbpe"/><path class="u53z4igoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-voice" /></template>
