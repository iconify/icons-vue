<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiap8ebun.css';
import '../../css/r/r_hb2znwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="r_hb2znwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-sublime" /></template>
