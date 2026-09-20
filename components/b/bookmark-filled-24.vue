<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft_pidc4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft_pidc4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bookmark-filled-24" /></template>
