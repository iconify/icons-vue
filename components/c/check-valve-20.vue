<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1cbt0mon.css';
import '../../css/f/fx-nsmbzv.css';
import '../../css/l/lnppjcb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1cbt0mon"/><path class="fx-nsmbzv"/><path class="lnppjcb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:check-valve-20" /></template>
