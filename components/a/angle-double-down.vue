<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqhgy604n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhgy604n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-double-down" /></template>
