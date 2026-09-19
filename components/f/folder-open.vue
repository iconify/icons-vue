<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruu0d2g3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ruu0d2g3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-open" /></template>
