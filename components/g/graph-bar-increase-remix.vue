<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt8tarx-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qt8tarx-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-bar-increase-remix" /></template>
