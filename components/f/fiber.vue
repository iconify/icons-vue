<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf_vahzfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gf_vahzfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:fiber" /></template>
