<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spajzybyt.css';
import '../../css/h/hhwq3mbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spajzybyt"/><path class="hhwq3mbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-mock" /></template>
