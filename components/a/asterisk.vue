<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwb8jdbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwb8jdbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:asterisk" /></template>
