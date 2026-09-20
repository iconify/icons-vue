<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab1a5obfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab1a5obfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:civo" /></template>
