<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1fdsqbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1fdsqbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dissatisfaction-filled" /></template>
