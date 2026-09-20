<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg_cwepzi.css';
import '../../css/t/tvqx1abby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sg_cwepzi"/><path class="tvqx1abby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-stack-open" /></template>
