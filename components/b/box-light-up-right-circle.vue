<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrc83gbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wrc83gbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-right-circle" /></template>
