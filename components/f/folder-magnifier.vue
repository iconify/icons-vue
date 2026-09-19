<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unjrerbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="unjrerbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-magnifier" /></template>
