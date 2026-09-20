<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_94jmbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s_94jmbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:binoculars-remix" /></template>
