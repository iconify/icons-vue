<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr0kbqbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0kbqbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-pause" /></template>
