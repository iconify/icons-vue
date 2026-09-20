<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb8vcux9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb8vcux9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-search-corner" /></template>
