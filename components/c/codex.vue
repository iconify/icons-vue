<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iymj-b0-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iymj-b0-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:codex" /></template>
