<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st8y7bi7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="st8y7bi7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:informatica" /></template>
