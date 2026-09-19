<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqgo409cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uqgo409cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:inertiajs" /></template>
