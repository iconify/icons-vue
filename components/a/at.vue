<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jap95xb6l.css';
import '../../css/g/gkzp8sbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jap95xb6l"/><path class="gkzp8sbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:at" /></template>
