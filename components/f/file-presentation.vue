<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbigfv4ml.css';
import '../../css/x/xi9vqyepo.css';
import '../../css/e/ey3ijkbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbigfv4ml"/><path class="xi9vqyepo"/><path class="ey3ijkbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-presentation" /></template>
