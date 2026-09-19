<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmo02zb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nmo02zb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:azure" /></template>
