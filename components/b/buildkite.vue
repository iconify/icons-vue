<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq4svq8ys.css';
import '../../css/r/rbmgisbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eq4svq8ys"/><path class="rbmgisbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:buildkite" /></template>
