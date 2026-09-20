<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9jj03bpd.css';
import '../../css/r/rd09_mylf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m9jj03bpd"/><path class="rd09_mylf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-license" /></template>
