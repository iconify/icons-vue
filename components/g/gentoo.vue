<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz464fbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="iz464fbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gentoo" /></template>
