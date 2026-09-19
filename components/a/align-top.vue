<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud6fnccuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ud6fnccuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:align-top" /></template>
