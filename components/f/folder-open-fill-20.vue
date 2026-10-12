<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8_2a_bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b8_2a_bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folder-open-fill-20" /></template>
