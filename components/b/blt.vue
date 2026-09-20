<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnrdf8biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnrdf8biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blt" /></template>
