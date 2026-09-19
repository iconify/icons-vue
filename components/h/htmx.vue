<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n92am5kgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n92am5kgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:htmx" /></template>
