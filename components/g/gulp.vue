<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aep8f2bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="aep8f2bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gulp" /></template>
