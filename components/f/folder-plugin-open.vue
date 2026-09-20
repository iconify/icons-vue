<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8r7eptda.css';
import '../../css/y/ykmbv_xzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u8r7eptda"/><path class="ykmbv_xzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-plugin-open" /></template>
