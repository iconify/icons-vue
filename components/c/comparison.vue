<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4g7fn3kg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z4g7fn3kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:comparison" /></template>
