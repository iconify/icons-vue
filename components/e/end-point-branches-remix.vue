<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ymsbbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j5ymsbbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:end-point-branches-remix" /></template>
