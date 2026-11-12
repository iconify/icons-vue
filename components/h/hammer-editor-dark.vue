<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2v_2ib2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2v_2ib2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hammer-editor-dark" /></template>
