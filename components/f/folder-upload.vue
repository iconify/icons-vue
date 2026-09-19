<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9ev8c_0g.css';
import '../../css/j/jfo5ug-pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer u9ev8c_0g"/><path class="duoicon-primary-layer jfo5ug-pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:folder-upload" /></template>
