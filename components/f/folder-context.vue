<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_8dvglkn.css';
import '../../css/m/ms_cpibuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t_8dvglkn"/><path class="ms_cpibuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-context" /></template>
