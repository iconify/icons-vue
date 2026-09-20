<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7n2shh1v.css';
import '../../css/l/l6g1gqb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p7n2shh1v"/><path class="l6g1gqb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-api" /></template>
