<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmg9ivb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmg9ivb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:banknote-fill-round" /></template>
