<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8usf-rtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8usf-rtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:file-lines" /></template>
