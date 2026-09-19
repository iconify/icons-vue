<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok-rcqbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":24};
const content = `<path class="ok-rcqbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:check" /></template>
