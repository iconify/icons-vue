<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnlctj5oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jnlctj5oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:astroluma-dark" /></template>
