<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe_1fl_8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oe_1fl_8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chevron-lg-down" /></template>
