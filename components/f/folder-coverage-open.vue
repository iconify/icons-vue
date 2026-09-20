<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpc9hgrvp.css';
import '../../css/b/bwv8_8upf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mpc9hgrvp"/><path class="bwv8_8upf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-coverage-open" /></template>
