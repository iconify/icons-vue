<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c38ac1bbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c38ac1bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:diaspora" /></template>
