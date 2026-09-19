<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpo3m08or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wpo3m08or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-github" /></template>
