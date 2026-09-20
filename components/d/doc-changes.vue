<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tesehiy_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tesehiy_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:doc-changes" /></template>
