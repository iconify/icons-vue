<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu4v59b1a.css';
import '../../css/d/dc02pybze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu4v59b1a"/><path class="dc02pybze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:crunchbase" /></template>
