<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwjft7bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwjft7bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gnome" /></template>
