<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgjiwf5-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="fgjiwf5-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:asset-outdoor" /></template>
