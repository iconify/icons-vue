<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uny7lqboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uny7lqboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ink-alert" /></template>
