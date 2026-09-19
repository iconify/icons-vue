<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwkk87onx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pwkk87onx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:css3" /></template>
