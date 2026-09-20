<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j51w7z-wj.css';
import '../../css/q/qg43yj1um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j51w7z-wj"/><path class="qg43yj1um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:location-arrow-circle-o" /></template>
