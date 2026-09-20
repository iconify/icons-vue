<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkb61lbnd.css';
import '../../css/d/dpzlhg-bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkb61lbnd"/><path class="dpzlhg-bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-decorators-open" /></template>
