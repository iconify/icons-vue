<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ldh79sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n_ldh79sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:fsharp" /></template>
