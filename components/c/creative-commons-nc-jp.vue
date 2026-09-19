<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-92f7qth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b-92f7qth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:creative-commons-nc-jp" /></template>
