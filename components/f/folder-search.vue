<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo0xyvbqi.css';
import '../../css/g/g5pmz6bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eo0xyvbqi"/><path class="g5pmz6bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-search" /></template>
