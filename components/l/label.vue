<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggl5p0bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ggl5p0bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:label" /></template>
