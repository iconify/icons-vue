<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huh3he71t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="huh3he71t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flip-vertical-outline" /></template>
