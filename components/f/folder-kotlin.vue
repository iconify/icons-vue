<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ad0g2qb.css';
import '../../css/o/ogtj31bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l-ad0g2qb"/><path class="ogtj31bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-kotlin" /></template>
