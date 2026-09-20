<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7-mkdg7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l7-mkdg7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:false-positive" /></template>
