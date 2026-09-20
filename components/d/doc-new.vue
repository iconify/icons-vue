<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmp6hg-nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dmp6hg-nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-new" /></template>
