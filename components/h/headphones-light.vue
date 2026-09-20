<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u506o2_2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u506o2_2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headphones-light" /></template>
