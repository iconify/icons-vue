<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmq9zib2l.css';
import '../../css/g/gv3xfmb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wmq9zib2l"/><path class="gv3xfmb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:insert" /></template>
