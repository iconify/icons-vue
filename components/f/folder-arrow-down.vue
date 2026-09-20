<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqbqh9b-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqbqh9b-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-arrow-down" /></template>
