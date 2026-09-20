<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukvws-bxw.css';
import '../../css/j/jrlnttbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ukvws-bxw"/><path class="jrlnttbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-resolver" /></template>
