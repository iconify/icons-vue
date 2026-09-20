<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0c1nwb0d.css';
import '../../css/c/c1xpauj8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j0c1nwb0d"/><path class="c1xpauj8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-lib-open" /></template>
