<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwg2hccwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kwg2hccwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:duc" /></template>
