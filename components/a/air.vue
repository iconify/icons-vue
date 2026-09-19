<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sr4tues1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sr4tues1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:air" /></template>
