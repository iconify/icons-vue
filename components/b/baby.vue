<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d37911_pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d37911_pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:baby" /></template>
