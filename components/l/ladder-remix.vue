<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuby15b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vuby15b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ladder-remix" /></template>
