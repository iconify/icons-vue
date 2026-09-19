<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_diomx1n.css';
import '../../css/d/dki33cb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="o_diomx1n"/><path class="dki33cb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:lock" /></template>
