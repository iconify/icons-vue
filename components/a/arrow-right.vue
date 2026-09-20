<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmj801byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jmj801byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:arrow-right" /></template>
