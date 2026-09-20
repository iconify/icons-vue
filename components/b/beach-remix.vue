<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqakt6x8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jqakt6x8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:beach-remix" /></template>
