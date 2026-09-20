<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao4bbvbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ao4bbvbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:list" /></template>
