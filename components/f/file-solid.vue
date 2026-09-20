<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztmcp1b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ztmcp1b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-solid" /></template>
