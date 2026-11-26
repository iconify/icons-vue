<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcsw5fyhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gcsw5fyhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:binijs" /></template>
