<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csnou1l8n.css';
import '../../css/z/z6oybf-di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="csnou1l8n"/><path class="z6oybf-di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bug-o" /></template>
