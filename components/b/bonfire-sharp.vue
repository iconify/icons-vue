<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqndebbwd.css';
import '../../css/d/d3236htcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqndebbwd"/><path class="d3236htcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bonfire-sharp" /></template>
