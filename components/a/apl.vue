<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dff5oixmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dff5oixmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apl" /></template>
