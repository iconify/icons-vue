<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo0lwublr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo0lwublr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:brackets" /></template>
