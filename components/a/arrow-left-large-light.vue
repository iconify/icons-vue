<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d49rtyo5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d49rtyo5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-left-large-light" /></template>
