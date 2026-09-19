<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlznm7l6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="zlznm7l6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:github-alt" /></template>
