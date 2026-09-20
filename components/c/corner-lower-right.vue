<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx06-ybtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx06-ybtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:corner-lower-right" /></template>
