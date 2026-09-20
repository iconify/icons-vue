<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s27ky2-ij.css';
import '../../css/s/sga5kfb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s27ky2-ij"/><path class="sga5kfb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-admin-open" /></template>
