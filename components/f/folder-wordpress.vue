<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcjmcxbsc.css';
import '../../css/i/ilpzg4xos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hcjmcxbsc"/><path class="ilpzg4xos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-wordpress" /></template>
