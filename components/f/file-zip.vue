<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bud3f4goj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="bud3f4goj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-zip" /></template>
