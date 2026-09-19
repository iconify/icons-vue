<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehapg43cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ehapg43cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:firefox" /></template>
