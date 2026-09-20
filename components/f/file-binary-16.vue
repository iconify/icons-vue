<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhhguccsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rhhguccsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-binary-16" /></template>
