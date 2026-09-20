<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg7s50srv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rg7s50srv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:hierarchy-15-remix" /></template>
