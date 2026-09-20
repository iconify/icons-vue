<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t32cmqbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t32cmqbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hard-drive-2-fill" /></template>
