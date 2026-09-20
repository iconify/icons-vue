<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z929_bb-t.css';
import '../../css/v/v_12yfv8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z929_bb-t"/><path class="v_12yfv8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:cross-in-circle-empty" /></template>
