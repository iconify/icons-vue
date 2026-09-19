<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if349kbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="if349kbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:framer" /></template>
