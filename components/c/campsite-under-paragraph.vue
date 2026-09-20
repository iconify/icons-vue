<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbm4d9pym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nbm4d9pym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-under-paragraph" /></template>
