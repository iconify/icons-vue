<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-kvgqbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-kvgqbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-minimalistic-square-2-outline" /></template>
