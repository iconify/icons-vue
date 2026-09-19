<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyoxpkbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyoxpkbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:flyadeal" /></template>
