<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pan31eb4g.css';
import '../../css/j/jef3z0auc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pan31eb4g"/><path class="jef3z0auc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-php-open" /></template>
