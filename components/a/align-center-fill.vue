<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2-_2ac-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-_2ac-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-fill" /></template>
