<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oembw3b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oembw3b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:kerb-lowered-under-shoe" /></template>
