<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5fxn4-5j.css';
import '../../css/i/izbcw3uam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5fxn4-5j"/><path class="izbcw3uam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-bluetooth" /></template>
