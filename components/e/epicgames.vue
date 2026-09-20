<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnw_dv-nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnw_dv-nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:epicgames" /></template>
