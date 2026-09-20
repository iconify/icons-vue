<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5i70lbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5i70lbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:adguard-logo-bold" /></template>
