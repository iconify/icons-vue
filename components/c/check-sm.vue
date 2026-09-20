<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nml4g8bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="nml4g8bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:check-sm" /></template>
