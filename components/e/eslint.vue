<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpre71u6z.css';
import '../../css/i/i19bypv0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lpre71u6z"/><path class="i19bypv0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:eslint" /></template>
