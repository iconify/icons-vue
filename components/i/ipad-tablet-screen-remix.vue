<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfw785bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jfw785bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:ipad-tablet-screen-remix" /></template>
