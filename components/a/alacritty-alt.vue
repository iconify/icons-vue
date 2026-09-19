<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_f4z8bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c_f4z8bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:alacritty-alt" /></template>
