<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh-kbll_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gh-kbll_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:invisible-2-remix" /></template>
