<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-icjnfkk.css';
import '../../css/p/pslrgkb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-icjnfkk"/><path class="pslrgkb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deepinfra" /></template>
