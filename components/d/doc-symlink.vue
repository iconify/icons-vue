<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2d47fcwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d2d47fcwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-symlink" /></template>
