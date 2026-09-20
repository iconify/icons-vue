<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcny2x1-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcny2x1-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-square-filled" /></template>
