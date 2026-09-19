<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt5-h7irr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bt5-h7irr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:calendar" /></template>
