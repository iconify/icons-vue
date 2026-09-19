<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5y09czkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5y09czkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:devcontainer" /></template>
