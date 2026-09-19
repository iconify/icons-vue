<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8p9iwiog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="l8p9iwiog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:apache" /></template>
