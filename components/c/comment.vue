<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0sz5dkww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0sz5dkww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:comment" /></template>
