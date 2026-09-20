<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hor2v3luj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hor2v3luj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:git-repository-private-fill" /></template>
