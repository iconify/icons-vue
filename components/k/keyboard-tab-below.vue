<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwl893x-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dwl893x-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:keyboard-tab-below" /></template>
