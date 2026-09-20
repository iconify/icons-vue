<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtmc67bsf.css';
import '../../css/l/lf6x23bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jtmc67bsf"/><path class="lf6x23bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-event-open" /></template>
