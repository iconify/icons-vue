<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5au4v4yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5au4v4yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:align-justify" /></template>
