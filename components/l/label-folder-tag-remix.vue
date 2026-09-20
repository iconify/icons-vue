<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwu3gcbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fwu3gcbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:label-folder-tag-remix" /></template>
