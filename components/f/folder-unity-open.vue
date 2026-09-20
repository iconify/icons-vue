<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx2l3o9hm.css';
import '../../css/c/catkmrzgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gx2l3o9hm"/><path class="catkmrzgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-unity-open" /></template>
