<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5nny4b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b5nny4b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ifttt" /></template>
