<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-ohpqbby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ohpqbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-minus-outline" /></template>
