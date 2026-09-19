<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzi66zbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzi66zbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-heart" /></template>
