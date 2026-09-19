<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3k3xebqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e3k3xebqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:codeberg" /></template>
