<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tei0bgeom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tei0bgeom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emailimport" /></template>
