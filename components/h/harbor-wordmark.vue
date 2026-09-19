<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc8luvptp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zc8luvptp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:harbor-wordmark" /></template>
