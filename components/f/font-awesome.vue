<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl9n98xsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jl9n98xsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:font-awesome" /></template>
