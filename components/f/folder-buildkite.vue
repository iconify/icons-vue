<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz37bn_-f.css';
import '../../css/m/mcl56li3l.css';
import '../../css/n/nadh9-zvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pz37bn_-f"/><path class="mcl56li3l"/><path class="nadh9-zvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-buildkite" /></template>
