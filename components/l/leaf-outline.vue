<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uif2hsb6m.css';
import '../../css/m/m-2igxbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uif2hsb6m"/><path class="m-2igxbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:leaf-outline" /></template>
