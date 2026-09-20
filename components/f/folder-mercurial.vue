<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wve-dxbgv.css';
import '../../css/i/ixz4scd6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wve-dxbgv"/><path class="ixz4scd6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-mercurial" /></template>
