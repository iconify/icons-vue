<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b276a-bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="b276a-bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:checkmark" /></template>
