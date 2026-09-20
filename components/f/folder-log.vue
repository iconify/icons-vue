<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj5g77b1a.css';
import '../../css/t/t7parlbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tj5g77b1a"/><path class="t7parlbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-log" /></template>
