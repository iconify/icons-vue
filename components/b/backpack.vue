<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf0f0uh5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0f0uh5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:backpack" /></template>
