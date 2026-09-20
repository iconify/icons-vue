<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe6i24l2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe6i24l2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:diamond-percent" /></template>
