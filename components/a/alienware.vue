<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czj-ojuap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czj-ojuap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alienware" /></template>
