<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygtkysbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ygtkysbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:archive-box-remix" /></template>
