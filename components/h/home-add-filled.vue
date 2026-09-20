<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji8riebbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ji8riebbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-add-filled" /></template>
