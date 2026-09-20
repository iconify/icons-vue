<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mks-38b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mks-38b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fork-knife" /></template>
