<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k08ifl9af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k08ifl9af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:alien-remix" /></template>
