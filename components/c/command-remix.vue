<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny36t5b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ny36t5b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:command-remix" /></template>
