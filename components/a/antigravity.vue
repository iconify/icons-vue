<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt9w92biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lt9w92biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:antigravity" /></template>
