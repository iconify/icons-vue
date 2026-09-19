<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1ofj0jgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ofj0jgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:git-fork" /></template>
