<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spajzybyt.css';
import '../../css/t/t_5urzb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="spajzybyt"/><path class="t_5urzb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-template" /></template>
