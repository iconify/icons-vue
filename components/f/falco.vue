<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jntr1kbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jntr1kbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:falco" /></template>
