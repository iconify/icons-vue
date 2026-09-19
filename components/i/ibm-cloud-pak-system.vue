<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gids-nb6q.css';
import '../../css/h/h3tk0hycl.css';
import '../../css/f/f86xz6sdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gids-nb6q"/><path class="h3tk0hycl"/><path class="f86xz6sdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-system" /></template>
