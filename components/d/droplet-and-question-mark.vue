<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cljdfj5ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cljdfj5ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:droplet-and-question-mark" /></template>
