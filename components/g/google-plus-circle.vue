<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcnej6jbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rcnej6jbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:google-plus-circle" /></template>
