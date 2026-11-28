<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jntxs735o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jntxs735o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:border-bottom-solid" /></template>
