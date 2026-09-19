<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugghz5fzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugghz5fzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:circle-o-notch" /></template>
