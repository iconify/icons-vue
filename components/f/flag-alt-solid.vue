<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8nmwqbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y8nmwqbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flag-alt-solid" /></template>
