<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9h9hwd0t.css';
import '../../css/g/g1xl1cbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f9h9hwd0t"/><path class="g1xl1cbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-moved-16" /></template>
