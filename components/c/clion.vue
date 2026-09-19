<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uusi_52_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uusi_52_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:clion" /></template>
