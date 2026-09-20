<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8vs4jsld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8vs4jsld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:buildings-2-outline" /></template>
