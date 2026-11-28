<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfk181vqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfk181vqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:grapes" /></template>
