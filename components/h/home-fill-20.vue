<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chf27ccsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="chf27ccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:home-fill-20" /></template>
