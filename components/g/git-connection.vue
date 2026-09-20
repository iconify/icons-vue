<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp6pvjrvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp6pvjrvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-connection" /></template>
