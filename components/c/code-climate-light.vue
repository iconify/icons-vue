<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgddl0bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="qgddl0bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:code-climate-light" /></template>
