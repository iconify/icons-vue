<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps-bh4bky.css';
import '../../css/j/j9noiqajd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ps-bh4bky"/><path class="j9noiqajd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-quasar-open" /></template>
