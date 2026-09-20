<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqh16pv3v.css';
import '../../css/l/li38icbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yqh16pv3v"/><path class="li38icbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-custom" /></template>
