<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9wagqbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9wagqbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gitlab-line" /></template>
