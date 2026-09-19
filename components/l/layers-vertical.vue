<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln33uabds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ln33uabds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:layers-vertical" /></template>
