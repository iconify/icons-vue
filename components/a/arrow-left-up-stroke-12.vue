<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/digprjbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="digprjbte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-up-stroke-12" /></template>
