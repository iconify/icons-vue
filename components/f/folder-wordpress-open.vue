<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xolmzhbns.css';
import '../../css/i/ilpzg4xos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xolmzhbns"/><path class="ilpzg4xos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-wordpress-open" /></template>
