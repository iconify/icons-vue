<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdk8ml8uk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdk8ml8uk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-classic-light" /></template>
