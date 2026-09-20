<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlcjxsb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlcjxsb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:deepmind-google" /></template>
