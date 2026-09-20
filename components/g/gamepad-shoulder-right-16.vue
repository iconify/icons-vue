<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mli95hbir.css';
import '../../css/w/wcc88lbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mli95hbir"/><path clip-rule="evenodd" class="wcc88lbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-shoulder-right-16" /></template>
