<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/biji12x1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="biji12x1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:gist" /></template>
