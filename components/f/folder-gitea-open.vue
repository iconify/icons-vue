<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp948_bll.css';
import '../../css/i/ib8s1i8wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hp948_bll"/><path class="ib8s1i8wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-gitea-open" /></template>
