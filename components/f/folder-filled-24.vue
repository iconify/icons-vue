<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgn4b_b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgn4b_b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-filled-24" /></template>
