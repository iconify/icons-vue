<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwcxw0bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bwcxw0bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:face-very-sad-fill-16" /></template>
