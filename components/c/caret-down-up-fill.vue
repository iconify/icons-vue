<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euj3ffbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="euj3ffbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:caret-down-up-fill" /></template>
