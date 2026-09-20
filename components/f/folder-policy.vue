<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhg495fle.css';
import '../../css/w/wsrr0dbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nhg495fle"/><path class="wsrr0dbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-policy" /></template>
