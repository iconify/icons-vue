<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcbu6ibrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vcbu6ibrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:file-tree" /></template>
