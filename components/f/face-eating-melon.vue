<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p84hqbcae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p84hqbcae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-eating-melon" /></template>
