<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2la65t2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="p2la65t2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:igloo" /></template>
