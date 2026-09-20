<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnr1cdgtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnr1cdgtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headphones-off-sharp" /></template>
