<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prjf5xbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":16};
const content = `<path class="prjf5xbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dash" /></template>
