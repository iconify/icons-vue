<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4160sb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h4160sb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:folder-images" /></template>
