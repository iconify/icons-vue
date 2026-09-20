<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phu1k1bve.css';
import '../../css/v/v-975mjhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="phu1k1bve"/><path class="v-975mjhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-lua" /></template>
