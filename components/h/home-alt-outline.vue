<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqvhg5dzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqvhg5dzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:home-alt-outline" /></template>
