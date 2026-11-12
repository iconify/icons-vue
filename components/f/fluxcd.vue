<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4n_gx7bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t4n_gx7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:fluxcd" /></template>
