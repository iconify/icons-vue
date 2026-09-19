<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkk7ktbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dkk7ktbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:box" /></template>
