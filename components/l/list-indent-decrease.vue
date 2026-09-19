<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp3y-jbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp3y-jbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-indent-decrease" /></template>
