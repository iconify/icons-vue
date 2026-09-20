<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av1ilqbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="av1ilqbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:full-height-turnstile" /></template>
