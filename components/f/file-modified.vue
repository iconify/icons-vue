<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4us--h_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w4us--h_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:file-modified" /></template>
