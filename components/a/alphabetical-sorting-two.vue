<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jro4d0bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jro4d0bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:alphabetical-sorting-two" /></template>
