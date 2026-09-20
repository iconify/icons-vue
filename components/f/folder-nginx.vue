<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcy98sbxp.css';
import '../../css/q/q6t1v8bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kcy98sbxp"/><path class="q6t1v8bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-nginx" /></template>
