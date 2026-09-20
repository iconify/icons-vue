<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zar8htjha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zar8htjha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:loading-horizontal-2-remix" /></template>
