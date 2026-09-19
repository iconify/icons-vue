<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp65h5bgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xp65h5bgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:cloud-upload" /></template>
