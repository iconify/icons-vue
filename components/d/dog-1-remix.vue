<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srsz1tbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="srsz1tbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:dog-1-remix" /></template>
