<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-d3uqbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-d3uqbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:dice-sharp" /></template>
