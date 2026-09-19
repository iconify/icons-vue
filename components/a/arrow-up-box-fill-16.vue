<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fckspfb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fckspfb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-up-box-fill-16" /></template>
