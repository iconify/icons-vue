<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymh664bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ymh664bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:cup-with-straw" /></template>
