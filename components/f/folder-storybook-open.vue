<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-td7-p-y.css';
import '../../css/h/hhhxw4j6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-td7-p-y"/><path class="hhhxw4j6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-storybook-open" /></template>
