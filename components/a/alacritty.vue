<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r80pjdb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r80pjdb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alacritty" /></template>
